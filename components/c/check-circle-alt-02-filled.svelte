<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sygifnnbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sygifnnbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:check-circle-alt-02-filled" {...props}></Icon>
