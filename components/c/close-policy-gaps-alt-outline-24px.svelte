<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2nz4slzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w2nz4slzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:close-policy-gaps-alt-outline-24px" {...props}></Icon>
