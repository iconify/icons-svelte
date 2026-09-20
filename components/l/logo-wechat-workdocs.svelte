<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cho9kmb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cho9kmb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-wechat-workdocs" {...props}></Icon>
