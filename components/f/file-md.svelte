<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di8ni_dks.css';
import '../../css/z/z_6vl9bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di8ni_dks"/><path class="z_6vl9bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:file-md" {...props}></Icon>
