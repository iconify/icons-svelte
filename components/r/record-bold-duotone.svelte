<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7ssc3b8h.css';
import '../../css/z/zo3cxx6gk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="i7ssc3b8h"/><path clip-rule="evenodd" class="zo3cxx6gk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:record-bold-duotone" {...props}></Icon>
