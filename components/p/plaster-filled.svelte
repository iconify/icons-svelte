<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axi7sujok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="axi7sujok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:plaster-filled" {...props}></Icon>
