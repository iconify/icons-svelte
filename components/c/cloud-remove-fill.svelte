<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx92xrs1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hx92xrs1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cloud-remove-fill" {...props}></Icon>
