<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trwtybczh.css';
import '../../css/s/s39r46bkt.css';
import '../../css/h/hoofw7boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trwtybczh"/><path class="s39r46bkt"/><path class="hoofw7boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fio" {...props}></Icon>
