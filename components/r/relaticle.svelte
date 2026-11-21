<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui6tf0b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ui6tf0b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:relaticle" {...props}></Icon>
