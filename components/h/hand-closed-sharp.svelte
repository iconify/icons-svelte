<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io7iwj50t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io7iwj50t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hand-closed-sharp" {...props}></Icon>
