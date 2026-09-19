<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf2e-874i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uf2e-874i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:glass-alt" {...props}></Icon>
