<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q953-nbum.css';
import '../../css/u/u9-d979uw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ouiIcon__fillSecondary q953-nbum"/><path class="u9-d979uw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-sql" {...props}></Icon>
