<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i17tvmbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i17tvmbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:cloud-alt-fill" {...props}></Icon>
