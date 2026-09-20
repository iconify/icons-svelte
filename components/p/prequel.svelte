<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl1cnobzu.css';
import '../../css/q/qgzh5-i-h.css';
import '../../css/o/ozav58bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fl1cnobzu"/><circle class="qgzh5-i-h"/><circle class="ozav58bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:prequel" {...props}></Icon>
