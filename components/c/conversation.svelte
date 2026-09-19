<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uedtu89cj.css';
import '../../css/b/b2m7ke2wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uedtu89cj"/><path class="b2m7ke2wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:conversation" {...props}></Icon>
