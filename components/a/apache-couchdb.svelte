<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8pbo6bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8pbo6bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:apache-couchdb" {...props}></Icon>
