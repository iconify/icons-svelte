<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7aemk5fe.css';
import '../../css/x/x41xvfi0c.css';
import '../../css/y/y97ssxb3n.css';
import '../../css/m/m2h8cktnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7aemk5fe"/><path class="x41xvfi0c"/><path class="y97ssxb3n"/><path clip-rule="evenodd" class="m2h8cktnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lock-password-unlocked-outline" {...props}></Icon>
