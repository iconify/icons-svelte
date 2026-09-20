<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi2419bxd.css';
import '../../css/h/hcenjub2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi2419bxd"/><path class="hcenjub2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-light" {...props}></Icon>
