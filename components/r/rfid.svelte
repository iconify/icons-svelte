<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk6ielbwq.css';
import '../../css/c/c7gfsbb7m.css';
import '../../css/a/a1orltb6z.css';
import '../../css/n/nok52yrop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk6ielbwq"/><circle class="c7gfsbb7m"/><path class="a1orltb6z"/><path class="nok52yrop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:rfid" {...props}></Icon>
