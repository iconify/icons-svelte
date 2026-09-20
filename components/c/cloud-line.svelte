<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxttk3bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lxttk3bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:cloud-line" {...props}></Icon>
