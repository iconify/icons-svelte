<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbvbi9oey.css';
import '../../css/l/lp7eaq79j.css';
import '../../css/n/n1xy6nh9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbvbi9oey"/><path class="lp7eaq79j"/><circle class="n1xy6nh9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-joystick-button" {...props}></Icon>
