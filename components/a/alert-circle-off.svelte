<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft-5lzbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft-5lzbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alert-circle-off" {...props}></Icon>
