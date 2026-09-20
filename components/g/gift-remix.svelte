<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-9-ho40l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="o-9-ho40l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:gift-remix" {...props}></Icon>
