<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhyge19vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhyge19vm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:adjust-circle" {...props}></Icon>
