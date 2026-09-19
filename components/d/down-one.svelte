<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt47p46dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qt47p46dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:down-one" {...props}></Icon>
