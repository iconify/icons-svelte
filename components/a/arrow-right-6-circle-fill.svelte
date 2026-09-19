<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekn7hob8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ekn7hob8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-right-6-circle-fill" {...props}></Icon>
