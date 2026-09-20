<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnme3-bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qnme3-bhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:gender-androgyne" {...props}></Icon>
