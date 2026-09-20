<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-2o90bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-2o90bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:coding-apps-website-web-form-drop-down-menu-1-bold" {...props}></Icon>
