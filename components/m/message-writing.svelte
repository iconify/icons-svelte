<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pamsoyntu.css';
import '../../css/f/ftg34obra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pamsoyntu"/><path class="ftg34obra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:message-writing" {...props}></Icon>
