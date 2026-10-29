<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uswc0fr3j.css';
import '../../css/n/nu8i0-bfz.css';
import '../../css/d/dqe_68bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uswc0fr3j wm-k"/><path class="nu8i0-bfz wm-a"/><path class="dqe_68bhs wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:download" {...props}></Icon>
