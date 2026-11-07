<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln1f_4blw.css';
import '../../css/o/o1li7xbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln1f_4blw"/><path class="o1li7xbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:link-bold" {...props}></Icon>
