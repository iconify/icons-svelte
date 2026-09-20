<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6i-ucciw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d6i-ucciw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:change-background-transparent-remix" {...props}></Icon>
