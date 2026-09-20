<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye6tf12-p.css';
import '../../css/o/o84l7ebqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye6tf12-p"/><path class="o84l7ebqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:arhive-alt-small-duotone" {...props}></Icon>
