<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2bnn7ohn.css';
import '../../css/j/jkdbh9btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k2bnn7ohn"/><path class="jkdbh9btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paperclip-bold-duotone" {...props}></Icon>
