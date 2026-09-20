<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck1zpvp7z.css';
import '../../css/g/gv5ppo3az.css';
import '../../css/u/u4zjxwbyw.css';
import '../../css/h/hxq4vobqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck1zpvp7z"/><path class="gv5ppo3az"/><path class="u4zjxwbyw"/><path class="hxq4vobqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:paid" {...props}></Icon>
