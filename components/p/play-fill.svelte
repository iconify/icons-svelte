<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg6xhabdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pg6xhabdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:play-fill" {...props}></Icon>
