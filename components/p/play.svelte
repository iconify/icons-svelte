<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adnoxa.css';
import '../../css/s/so-from-38.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adnoxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:play" {...props}></Icon>
