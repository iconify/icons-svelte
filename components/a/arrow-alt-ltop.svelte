<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzn64jbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzn64jbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:arrow-alt-ltop" {...props}></Icon>
