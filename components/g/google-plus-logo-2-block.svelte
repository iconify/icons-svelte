<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6qek2uec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o6qek2uec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-plus-logo-2-block" {...props}></Icon>
