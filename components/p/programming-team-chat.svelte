<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/x-s2c-blu.css';
import '../../css/v/v6jh7nbwl.css';
import '../../css/s/ssflmdble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="x-s2c-blu"/><path class="v6jh7nbwl"/><path class="ssflmdble"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:programming-team-chat" {...props}></Icon>
