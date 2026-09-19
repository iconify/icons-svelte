<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jus2nxdev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jus2nxdev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:halloween-tomb" {...props}></Icon>
