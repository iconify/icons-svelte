<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx3heqy7f.css';
import '../../css/t/t5lk8xcct.css';
import '../../css/i/indyp0f7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ouiIcon__fillSecondary zx3heqy7f"/><path class="t5lk8xcct"/><path class="indyp0f7r ouiIcon__fillSecondary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-spaces" {...props}></Icon>
