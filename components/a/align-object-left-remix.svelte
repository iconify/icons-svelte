<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6rqx6bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="m6rqx6bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:align-object-left-remix" {...props}></Icon>
