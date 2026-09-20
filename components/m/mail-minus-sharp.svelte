<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovyazib-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovyazib-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mail-minus-sharp" {...props}></Icon>
