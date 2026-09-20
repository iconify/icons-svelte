<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxxm79pjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="xxxm79pjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mood-flat-solid" {...props}></Icon>
