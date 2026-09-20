<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akl-4bbmb.css';
import '../../css/b/b08tyi05f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akl-4bbmb"/><path class="b08tyi05f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-wechat-stroke-filled" {...props}></Icon>
