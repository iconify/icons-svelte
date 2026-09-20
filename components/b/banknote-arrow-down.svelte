<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gae93nb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gae93nb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:banknote-arrow-down" {...props}></Icon>
