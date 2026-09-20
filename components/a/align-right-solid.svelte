<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayhvrwn1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayhvrwn1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:align-right-solid" {...props}></Icon>
