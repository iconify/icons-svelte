<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta4ildugp.css';
import '../../css/g/gda8q7btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ta4ildugp"/><path class="gda8q7btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:notebook-48-bold" {...props}></Icon>
