<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmb3itboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mmb3itboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:car-filled" {...props}></Icon>
