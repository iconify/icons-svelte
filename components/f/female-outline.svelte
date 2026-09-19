<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpm4kob4e.css';
import '../../css/z/zbsn2h2kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="zpm4kob4e"/><path class="zbsn2h2kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:female-outline" {...props}></Icon>
