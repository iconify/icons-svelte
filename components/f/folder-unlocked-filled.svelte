<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-9fnb75y.css';
import '../../css/l/ls5757boo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-9fnb75y"/><path class="ls5757boo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:folder-unlocked-filled" {...props}></Icon>
