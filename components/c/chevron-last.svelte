<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptks6rh3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ptks6rh3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:chevron-last" {...props}></Icon>
