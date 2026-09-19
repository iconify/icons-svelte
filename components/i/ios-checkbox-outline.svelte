<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9m2_kb3v.css';
import '../../css/d/d9vrg4bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u9m2_kb3v"/><path class="d9vrg4bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-checkbox-outline" {...props}></Icon>
