<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txfzqa3vh.css';
import '../../css/o/ooafjrbnh.css';
import '../../css/m/mqpsn0bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txfzqa3vh"/><path class="ooafjrbnh"/><path class="mqpsn0bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:face-grin" {...props}></Icon>
