<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k697zn7dx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k697zn7dx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:copyright-alt-fill" {...props}></Icon>
