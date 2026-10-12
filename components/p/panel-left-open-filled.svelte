<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjq87kk7o.css';
import '../../css/t/taok2ubed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjq87kk7o"/><path clip-rule="evenodd" class="taok2ubed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:panel-left-open-filled" {...props}></Icon>
