<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sntqev2mw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sntqev2mw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:inner-shadow-left-filled" {...props}></Icon>
