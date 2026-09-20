<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojvj-2bxz.css';
import '../../css/g/giecwuhng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ojvj-2bxz ouiIcon__fillSecondary"/><path class="giecwuhng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-heartbeat" {...props}></Icon>
