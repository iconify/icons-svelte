<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_9cc6bpa.css';
import '../../css/g/gwt9xds0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n_9cc6bpa"/><path class="gwt9xds0b ouiIcon__fillSecondary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-app-search" {...props}></Icon>
