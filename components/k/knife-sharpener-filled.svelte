<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuvx7sbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iuvx7sbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:knife-sharpener-filled" {...props}></Icon>
