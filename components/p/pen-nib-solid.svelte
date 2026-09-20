<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crx6jyhul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crx6jyhul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:pen-nib-solid" {...props}></Icon>
