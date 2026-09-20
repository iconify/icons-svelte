<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h068x0bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h068x0bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:redhat" {...props}></Icon>
