<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb8nn8bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb8nn8bbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:no-expression-filled" {...props}></Icon>
