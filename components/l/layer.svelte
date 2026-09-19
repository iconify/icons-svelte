<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oew3rhbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oew3rhbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:layer" {...props}></Icon>
