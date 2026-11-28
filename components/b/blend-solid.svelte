<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4iq7xbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4iq7xbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:blend-solid" {...props}></Icon>
