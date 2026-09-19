<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljyhemvfh.css';
import '../../css/o/oigxjx0ho.css';
import '../../css/m/m8j-0ru9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ljyhemvfh"/><path class="oigxjx0ho"/><path class="m8j-0ru9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:factory" {...props}></Icon>
