<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ids8rjbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ids8rjbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:disable-alarm-solid" {...props}></Icon>
