<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogigqt7lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogigqt7lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:keyboard-round" {...props}></Icon>
