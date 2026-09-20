<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfxpjhf8j.css';
import '../../css/q/qn4nzybbc.css';
import '../../css/o/owvyp-b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sfxpjhf8j"/><path class="ouiIcon__fillSecondary qn4nzybbc"/><path class="owvyp-b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-security-analytics" {...props}></Icon>
