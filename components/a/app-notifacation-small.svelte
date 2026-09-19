<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sned-lbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="sned-lbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:app-notifacation-small" {...props}></Icon>
