<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0nd0wbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0nd0wbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dotted-letter-q" {...props}></Icon>
