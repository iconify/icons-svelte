<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6wss0byk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6wss0byk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:deepnote" {...props}></Icon>
