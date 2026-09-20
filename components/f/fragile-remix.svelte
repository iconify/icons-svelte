<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk79iejtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="uk79iejtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:fragile-remix" {...props}></Icon>
