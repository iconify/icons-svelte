<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3symwlop.css';
import '../../css/y/ypo2h9ruk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k3symwlop ouiIcon__fillSecondary"/><path class="ypo2h9ruk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-uptime" {...props}></Icon>
