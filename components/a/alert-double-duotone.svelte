<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh-7v-qvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh-7v-qvz primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:alert-double-duotone" {...props}></Icon>
