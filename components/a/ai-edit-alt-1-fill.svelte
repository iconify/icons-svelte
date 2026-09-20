<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz1qw1t2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz1qw1t2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-edit-alt-1-fill" {...props}></Icon>
