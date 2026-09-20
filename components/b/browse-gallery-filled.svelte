<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1asp8k8y.css';
import '../../css/m/moh8knr5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1asp8k8y"/><path class="moh8knr5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:browse-gallery-filled" {...props}></Icon>
