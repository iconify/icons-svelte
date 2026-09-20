<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb0pk6bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cb0pk6bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:disable-protection-remix" {...props}></Icon>
