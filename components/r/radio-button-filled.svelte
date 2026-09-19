<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdlttf2sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdlttf2sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:radio-button-filled" {...props}></Icon>
