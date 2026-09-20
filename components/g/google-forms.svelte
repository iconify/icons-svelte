<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e41tmoqhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e41tmoqhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:google-forms" {...props}></Icon>
