<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2u47pbtq.css';
import '../../css/p/pdguunnht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f2u47pbtq"/><path class="pdguunnht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:data-boolean-light" {...props}></Icon>
