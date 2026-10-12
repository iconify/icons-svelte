<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0dyn4o9i.css';
import '../../css/y/yzdgss0oz.css';
import '../../css/t/tdoi1abuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0dyn4o9i"/><path class="yzdgss0oz"/><path class="tdoi1abuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mails-filled" {...props}></Icon>
