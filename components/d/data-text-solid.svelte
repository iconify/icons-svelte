<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2_ajjtdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c2_ajjtdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:data-text-solid" {...props}></Icon>
