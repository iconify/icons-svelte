<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggv24lm0s.css';
import '../../css/q/qki1cds-o.css';
import '../../css/s/s6aioybet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer ggv24lm0s"/><path class="duoicon-primary-layer qki1cds-o"/><path class="duoicon-primary-layer s6aioybet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:g-translate" {...props}></Icon>
