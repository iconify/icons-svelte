<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsvm4h_mg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jsvm4h_mg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:halloween-pumpkin" {...props}></Icon>
