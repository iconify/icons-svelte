<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyqbx8b8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyqbx8b8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dotted-letter-z" {...props}></Icon>
