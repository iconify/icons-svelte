<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egg3vdbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="egg3vdbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-umbrella" {...props}></Icon>
