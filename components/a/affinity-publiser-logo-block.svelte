<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wydskcb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wydskcb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:affinity-publiser-logo-block" {...props}></Icon>
