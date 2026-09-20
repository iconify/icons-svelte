<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl9q4rsxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hl9q4rsxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-up-solid" {...props}></Icon>
