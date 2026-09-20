<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgsghmm9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgsghmm9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:massage" {...props}></Icon>
