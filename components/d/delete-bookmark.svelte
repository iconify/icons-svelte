<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7y5wkl1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c7y5wkl1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:delete-bookmark" {...props}></Icon>
