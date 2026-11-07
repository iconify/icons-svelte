<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9u-03p8n.css';
import '../../css/k/keuudrbox.css';
import '../../css/j/js631gbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q9u-03p8n"/><path class="keuudrbox"/><path class="js631gbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-left-open-bold-duotone" {...props}></Icon>
