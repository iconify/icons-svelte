<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh22bq98t.css';
import '../../css/x/x37i8o26b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fh22bq98t"/><path class="x37i8o26b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:link-48" {...props}></Icon>
