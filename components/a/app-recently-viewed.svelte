<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n90uq3bfu.css';
import '../../css/l/ljkivvbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n90uq3bfu"/><path class="ljkivvbav ouiIcon__fillSecondary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-recently-viewed" {...props}></Icon>
