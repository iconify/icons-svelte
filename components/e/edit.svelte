<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if7zwef8z.css';
import '../../css/b/bth-2hbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="if7zwef8z"/><path class="bth-2hbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:edit" {...props}></Icon>
