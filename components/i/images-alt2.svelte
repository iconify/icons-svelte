<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egirhzbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="egirhzbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:images-alt2" {...props}></Icon>
