<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzum_2d6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="bzum_2d6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:monstersinc" {...props}></Icon>
