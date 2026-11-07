<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2-x-cbeh.css';
import '../../css/j/j-2a-nbrj.css';
import '../../css/o/os9vkpw9m.css';
import '../../css/y/yl0s6gb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2-x-cbeh"/><path class="j-2a-nbrj"/><path class="os9vkpw9m"/><path class="yl0s6gb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:columns-4-bold-duotone" {...props}></Icon>
