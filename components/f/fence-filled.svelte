<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dboz0cbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dboz0cbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:fence-filled" {...props}></Icon>
