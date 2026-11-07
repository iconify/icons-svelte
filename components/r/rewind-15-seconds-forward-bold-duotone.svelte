<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ourjeh54g.css';
import '../../css/a/abd5czbav.css';
import '../../css/m/m87qi3nmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ourjeh54g"/><path class="abd5czbav"/><path clip-rule="evenodd" class="m87qi3nmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-15-seconds-forward-bold-duotone" {...props}></Icon>
