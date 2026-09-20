<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n64ezugia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n64ezugia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:radiopublic" {...props}></Icon>
